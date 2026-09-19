<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxt1kcc0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jxt1kcc0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sausages-alt-filled" /></template>
