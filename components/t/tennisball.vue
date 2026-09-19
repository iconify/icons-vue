<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tij9n_bhf.css';
import '../../css/e/ezspdub9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tij9n_bhf"/><path class="ezspdub9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:tennisball" /></template>
