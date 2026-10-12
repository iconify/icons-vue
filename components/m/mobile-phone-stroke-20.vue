<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9so18btn.css';
import '../../css/q/qlx4k6bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k9so18btn"/><path class="qlx4k6bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:mobile-phone-stroke-20" /></template>
