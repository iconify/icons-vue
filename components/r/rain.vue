<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvf5nbbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvf5nbbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:rain" /></template>
