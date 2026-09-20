<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spfb5kbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spfb5kbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rakuten-kobo" /></template>
