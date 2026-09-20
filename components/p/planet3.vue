<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nte24mkhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nte24mkhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:planet3" /></template>
