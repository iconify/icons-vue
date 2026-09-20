<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubk5lxb9k.css';
import '../../css/l/l8nart8of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubk5lxb9k"/><path clip-rule="evenodd" class="l8nart8of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:wallet-fill" /></template>
