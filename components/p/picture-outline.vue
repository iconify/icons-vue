<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr3v60brl.css';
import '../../css/v/v1qktebkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr3v60brl"/><path clip-rule="evenodd" class="v1qktebkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:picture-outline" /></template>
