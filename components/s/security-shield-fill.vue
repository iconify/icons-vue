<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxy4-i9_f.css';
import '../../css/t/tbnr6-0gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxy4-i9_f"/><path class="tbnr6-0gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:security-shield-fill" /></template>
