<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6xk0f5fc.css';
import '../../css/m/mi_ecrt5s.css';
import '../../css/b/bst7l4f5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f6xk0f5fc"/><path class="mi_ecrt5s"/><path class="bst7l4f5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minecraft-creeper" /></template>
