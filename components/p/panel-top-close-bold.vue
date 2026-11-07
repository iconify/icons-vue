<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9apwmb5t.css';
import '../../css/s/sks052b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b9apwmb5t"/><path class="sks052b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-top-close-bold" /></template>
