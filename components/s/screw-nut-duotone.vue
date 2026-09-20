<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfyl5d5vt.css';
import '../../css/c/c0mbupb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfyl5d5vt"/><path class="c0mbupb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:screw-nut-duotone" /></template>
