<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz__5zbvx.css';
import '../../css/j/jflyr3bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bz__5zbvx"/><path class="jflyr3bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ufo-bold" /></template>
