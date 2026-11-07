<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0a04rwms.css';
import '../../css/v/vlwih1bec.css';
import '../../css/l/lwsxc47kb.css';
import '../../css/k/kkhl62fff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z0a04rwms"/><path class="vlwih1bec"/><path class="lwsxc47kb"/><path class="kkhl62fff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:password-minimalistic-input-outline" /></template>
