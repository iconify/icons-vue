<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz_smq6vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="jz_smq6vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:yarn" /></template>
