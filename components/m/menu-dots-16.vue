<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpoi46r1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bpoi46r1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:menu-dots-16" /></template>
