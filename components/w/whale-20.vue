<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3t12zu5x.css';
import '../../css/i/io22ipbhv.css';
import '../../css/s/s63-krb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c3t12zu5x"/><path class="io22ipbhv"/><path class="s63-krb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:whale-20" /></template>
