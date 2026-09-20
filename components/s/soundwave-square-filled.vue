<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8da38ujk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v8da38ujk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:soundwave-square-filled" /></template>
