<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcoh9zb5r.css';
import '../../css/b/bve8ubjqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcoh9zb5r"/><path class="bve8ubjqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pwr" /></template>
