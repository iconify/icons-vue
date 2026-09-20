<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eady710yy.css';
import '../../css/i/i6lq1nbgv.css';
import '../../css/a/adi563bmp.css';
import '../../css/y/yc7bf-7cx.css';
import '../../css/r/r2w4zvd5e.css';
import '../../css/r/rrtyxrb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eady710yy"/><path class="i6lq1nbgv"/><path class="adi563bmp"/><path class="yc7bf-7cx"/><path class="r2w4zvd5e"/><path class="rrtyxrb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pydanticai" /></template>
