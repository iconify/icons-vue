<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eekfzqbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eekfzqbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-components-filled" /></template>
