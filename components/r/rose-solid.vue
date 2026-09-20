<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwuz2acbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jwuz2acbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:rose-solid" /></template>
