<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_kh4ijio.css';
import '../../css/p/phstewbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_kh4ijio"/><path class="phstewbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minus-bold-duotone" /></template>
