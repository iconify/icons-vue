<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwsxc47kb.css';
import '../../css/k/kkhl62fff.css';
import '../../css/o/o-v99zb0r.css';
import '../../css/h/hc3npei1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwsxc47kb"/><path class="kkhl62fff"/><path class="o-v99zb0r"/><path clip-rule="evenodd" class="hc3npei1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:password-minimalistic-outline" /></template>
