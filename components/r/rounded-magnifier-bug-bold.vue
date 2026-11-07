<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k90b1n3tg.css';
import '../../css/d/djha1e-kq.css';
import '../../css/m/mfnnv9grh.css';
import '../../css/t/thw7pvbec.css';
import '../../css/f/ftoixesmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k90b1n3tg"/><path clip-rule="evenodd" class="djha1e-kq"/><path class="mfnnv9grh"/><path class="thw7pvbec"/><path class="ftoixesmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-bug-bold" /></template>
