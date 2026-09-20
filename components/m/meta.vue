<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z06ze1bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z06ze1bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:meta" /></template>
