<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_smge2np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u_smge2np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:x-outline" /></template>
