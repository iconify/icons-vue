<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df1snmbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="df1snmbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tennis-2-bold" /></template>
