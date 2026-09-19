<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5fqy9gnu.css';
import '../../css/n/n9df1ve4c.css';
import '../../css/p/pi5jgob2x.css';
import '../../css/s/seim7uvii.css';
import '../../css/k/kho6i_baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q5fqy9gnu"/><path clip-rule="evenodd" class="n9df1ve4c"/><path clip-rule="evenodd" class="pi5jgob2x"/><path clip-rule="evenodd" class="seim7uvii"/><path clip-rule="evenodd" class="kho6i_baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:move-outline" /></template>
