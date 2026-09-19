<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb1vc-e3r.css';
import '../../css/x/xs322_bdu.css';
import '../../css/b/bm-jhkqqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="tb1vc-e3r"/><path class="xs322_bdu"/><path class="bm-jhkqqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:soccer" /></template>
