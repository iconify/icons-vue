<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo34r_bxy.css';
import '../../css/r/rsxgxvbwd.css';
import '../../css/v/vpom7jbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mo34r_bxy"/><path class="rsxgxvbwd"/><path clip-rule="evenodd" class="vpom7jbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:printer-bold" /></template>
