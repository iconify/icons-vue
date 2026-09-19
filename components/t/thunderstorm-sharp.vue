<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2xa0wbnt.css';
import '../../css/k/k5kt1he2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o2xa0wbnt"/><path class="k5kt1he2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:thunderstorm-sharp" /></template>
