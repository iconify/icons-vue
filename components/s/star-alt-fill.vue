<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y51pbhb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y51pbhb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:star-alt-fill" /></template>
