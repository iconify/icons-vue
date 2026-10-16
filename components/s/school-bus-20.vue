<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmf-m7bxg.css';
import '../../css/b/bcx0b9bfi.css';
import '../../css/h/hnhi0q8cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mmf-m7bxg"/><path class="bcx0b9bfi"/><path class="hnhi0q8cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:school-bus-20" /></template>
