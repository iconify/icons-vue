<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/m/mzohia.css';
import '../../css/z/zcfamf.css';
import '../../css/s/so-from-28.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c mzohia"/><path class="a0m25c zcfamf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:turn-sharp-right" /></template>
