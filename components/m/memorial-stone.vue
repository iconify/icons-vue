<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_rmtccot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k_rmtccot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone" /></template>
