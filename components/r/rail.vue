<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c466a129i.css';
import '../../css/z/zysww9lsz.css';
import '../../css/u/um8cl-nkw.css';
import '../../css/n/nzkrizz9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c466a129i"/><path class="zysww9lsz"/><path class="um8cl-nkw"/><path clip-rule="evenodd" class="nzkrizz9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rail" /></template>
