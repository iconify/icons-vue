<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp_wowb2j.css';
import '../../css/l/lt2mkcbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pp_wowb2j"/><path class="lt2mkcbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:port-output" /></template>
