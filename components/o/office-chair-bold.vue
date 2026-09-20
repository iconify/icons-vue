<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0p9_yb_k.css';
import '../../css/b/bu9ktetle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0p9_yb_k"/><path class="bu9ktetle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:office-chair-bold" /></template>
