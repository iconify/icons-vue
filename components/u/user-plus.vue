<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufkalqu2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ufkalqu2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-plus" /></template>
