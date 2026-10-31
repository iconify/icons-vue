<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piivihhtn.css';
import '../../css/i/i28mt_bch.css';
import '../../css/c/cwdx-acsy.css';
import '../../css/g/greuegb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="piivihhtn"/><path class="i28mt_bch"/><path class="cwdx-acsy"/><path class="greuegb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:paneuropean-union" /></template>
