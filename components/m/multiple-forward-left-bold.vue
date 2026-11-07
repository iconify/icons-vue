<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huxj-vhdc.css';
import '../../css/g/gqrwazmcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huxj-vhdc"/><path clip-rule="evenodd" class="gqrwazmcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:multiple-forward-left-bold" /></template>
