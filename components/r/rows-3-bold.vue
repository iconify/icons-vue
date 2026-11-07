<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgn7bubwt.css';
import '../../css/u/u-3cpkh9t.css';
import '../../css/f/fog6w8bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgn7bubwt"/><path class="u-3cpkh9t"/><path class="fog6w8bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rows-3-bold" /></template>
