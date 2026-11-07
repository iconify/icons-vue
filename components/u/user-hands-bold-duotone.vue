<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp66iosrg.css';
import '../../css/e/efszygbcr.css';
import '../../css/j/j855t9sbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp66iosrg"/><path class="efszygbcr"/><path class="j855t9sbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-hands-bold-duotone" /></template>
