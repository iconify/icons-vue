<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkb0jcelk.css';
import '../../css/b/breyi0bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkb0jcelk"/><path class="breyi0bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:radio-2-filled" /></template>
