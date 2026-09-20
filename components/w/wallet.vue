<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4_6atnkp.css';
import '../../css/l/lnxi9kb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4_6atnkp"/><circle class="lnxi9kb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:wallet" /></template>
