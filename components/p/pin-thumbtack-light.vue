<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw13j-wcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yw13j-wcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pin-thumbtack-light" /></template>
