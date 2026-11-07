<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9lkykbai.css';
import '../../css/p/pj1dodgri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9lkykbai"/><path class="pj1dodgri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:water-bold-duotone" /></template>
