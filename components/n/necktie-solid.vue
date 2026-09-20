<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk_ichqco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fk_ichqco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:necktie-solid" /></template>
