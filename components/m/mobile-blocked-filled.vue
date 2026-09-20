<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1aa_bxoc.css';
import '../../css/v/vibuei4ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1aa_bxoc"/><path class="vibuei4ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mobile-blocked-filled" /></template>
