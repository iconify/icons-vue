<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9ooe_rjk.css';
import '../../css/l/ld8afubkm.css';
import '../../css/n/n1ueciogc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u9ooe_rjk"/><path class="ld8afubkm"/><path clip-rule="evenodd" class="n1ueciogc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:passport-outline" /></template>
