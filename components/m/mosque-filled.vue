<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld4ywrboa.css';
import '../../css/q/qsvb7nb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld4ywrboa"/><path class="qsvb7nb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mosque-filled" /></template>
