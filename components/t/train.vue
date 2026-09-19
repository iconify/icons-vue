<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/becfcjx9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="becfcjx9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:train" /></template>
