<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpa070kua.css';
import '../../css/r/rsxgxvbwd.css';
import '../../css/z/z_ydjmbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zpa070kua"/><path class="rsxgxvbwd"/><path class="z_ydjmbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:printer-2-bold" /></template>
