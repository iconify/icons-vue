<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eym_g24ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="eym_g24ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:milk-package-small" /></template>
