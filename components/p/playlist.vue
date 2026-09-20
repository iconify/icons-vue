<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu31aqbef.css';
import '../../css/s/s1mar9bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu31aqbef"/><path class="s1mar9bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:playlist" /></template>
