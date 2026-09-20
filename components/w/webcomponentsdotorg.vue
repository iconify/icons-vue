<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suw6_ccmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suw6_ccmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:webcomponentsdotorg" /></template>
