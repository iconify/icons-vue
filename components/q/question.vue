<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlfg3onlw.css';
import '../../css/x/xa153ngzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlfg3onlw"/><circle class="xa153ngzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:question" /></template>
