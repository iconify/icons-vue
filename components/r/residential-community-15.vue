<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py8_zzozw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="py8_zzozw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:residential-community-15" /></template>
