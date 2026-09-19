<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntgros_9i.css';
import '../../css/x/xvmpc_kfa.css';
import '../../css/i/iyd3g3q8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ntgros_9i"/><path clip-rule="evenodd" class="xvmpc_kfa"/><path clip-rule="evenodd" class="iyd3g3q8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:totem-outline" /></template>
