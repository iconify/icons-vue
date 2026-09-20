<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw3q-gb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw3q-gb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:toolbox" /></template>
