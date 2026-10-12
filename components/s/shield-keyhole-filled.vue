<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykm2u3fal.css';
import '../../css/a/alh4zcbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykm2u3fal"/><path clip-rule="evenodd" class="alh4zcbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-keyhole-filled" /></template>
