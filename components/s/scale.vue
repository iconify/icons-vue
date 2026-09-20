<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq9jnpbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wq9jnpbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:scale" /></template>
