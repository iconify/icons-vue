<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze__gra_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze__gra_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:v2ex" /></template>
