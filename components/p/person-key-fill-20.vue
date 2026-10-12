<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et_p5ualv.css';
import '../../css/r/rudk2pbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="et_p5ualv"/><path class="rudk2pbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:person-key-fill-20" /></template>
