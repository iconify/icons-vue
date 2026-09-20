<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lof-am1yz.css';
import '../../css/p/pky0achnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lof-am1yz"/><path clip-rule="evenodd" class="pky0achnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:winrar-outline" /></template>
