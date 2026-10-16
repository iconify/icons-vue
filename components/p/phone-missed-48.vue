<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9xwe29zq.css';
import '../../css/l/lyuckzd_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b9xwe29zq"/><path class="lyuckzd_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-missed-48" /></template>
