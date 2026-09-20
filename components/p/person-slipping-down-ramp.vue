<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcqednb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kcqednb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-slipping-down-ramp" /></template>
