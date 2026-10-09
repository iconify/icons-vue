<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi9uwcchg.css';
import '../../css/k/kz2_3wbrk.css';
import '../../css/k/kn3-ey60h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zi9uwcchg"/><path class="kz2_3wbrk"/><path class="kn3-ey60h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:switch-closed-20-bold" /></template>
