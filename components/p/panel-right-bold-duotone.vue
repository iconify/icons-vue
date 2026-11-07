<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1nbikbny.css';
import '../../css/e/eaq7c7yzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1nbikbny"/><path class="eaq7c7yzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-right-bold-duotone" /></template>
