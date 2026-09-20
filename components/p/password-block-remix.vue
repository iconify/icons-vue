<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poqrz_5fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="poqrz_5fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:password-block-remix" /></template>
