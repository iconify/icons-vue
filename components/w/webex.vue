<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co3jv6bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co3jv6bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:webex" /></template>
