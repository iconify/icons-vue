<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdj9eybmg.css';
import '../../css/t/tgxkbbc5w.css';
import '../../css/p/p6a18oboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdj9eybmg"/><path class="tgxkbbc5w"/><path clip-rule="evenodd" class="p6a18oboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skateboard-bold-duotone" /></template>
