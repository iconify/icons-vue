<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsatub3fk.css';
import '../../css/c/c2aqpmbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dsatub3fk"/><path clip-rule="evenodd" class="c2aqpmbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:user-circle-solid" /></template>
