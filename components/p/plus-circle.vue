<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/m/maq17k.css';
import '../../css/u/ujphdc.css';
import '../../css/e/eaj3ug.css';
import '../../css/s/so-from-60.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c maq17k"/><path class="a0m25c ujphdc"/><path class="a0m25c eaj3ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:plus-circle" /></template>
