<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pka3_zpsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pka3_zpsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:tiktok" /></template>
