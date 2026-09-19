<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekh_09cjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekh_09cjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:tree-structure-filled" /></template>
