<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2qapdb-t.css';
import '../../css/q/qdsfr5okm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2qapdb-t"/><path clip-rule="evenodd" class="qdsfr5okm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:timer-solid" /></template>
