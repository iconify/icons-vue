<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvmgk0bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvmgk0bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:tag" /></template>
