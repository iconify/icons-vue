<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxxg4yb5u.css';
import '../../css/b/bfc02o_7t.css';
import '../../css/f/fjsi16b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vxxg4yb5u"/><path clip-rule="evenodd" class="bfc02o_7t"/><path class="fjsi16b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notebook-bookmark-bold" /></template>
