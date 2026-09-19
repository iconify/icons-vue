<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy9noxcnw.css';
import '../../css/o/o3c_lfbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cy9noxcnw"/><path class="o3c_lfbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:tag-o" /></template>
