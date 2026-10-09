<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-rlecbga.css';
import '../../css/g/gj8v89bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r-rlecbga"/><path class="gj8v89bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:video-20-bold" /></template>
