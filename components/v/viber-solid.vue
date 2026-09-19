<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na-kpqbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="na-kpqbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:viber-solid" /></template>
