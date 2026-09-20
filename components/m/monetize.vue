<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aochvebhn.css';
import '../../css/k/kxy6kzbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aochvebhn"/><path class="kxy6kzbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:monetize" /></template>
