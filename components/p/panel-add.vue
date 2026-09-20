<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8pydyx2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8pydyx2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:panel-add" /></template>
