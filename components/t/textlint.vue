<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijlxw4awb.css';
import '../../css/w/wru1txnso.css';
import '../../css/z/za3b9rblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ijlxw4awb"/><path class="wru1txnso"/><path class="za3b9rblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:textlint" /></template>
