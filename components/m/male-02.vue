<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgky8kb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgky8kb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:male-02" /></template>
