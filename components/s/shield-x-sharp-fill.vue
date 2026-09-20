<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcwq6x30k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bcwq6x30k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-x-sharp-fill" /></template>
