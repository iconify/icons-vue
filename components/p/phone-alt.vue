<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0fml_gub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="k0fml_gub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:phone-alt" /></template>
