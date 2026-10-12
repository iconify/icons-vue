<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_r-5l9bw.css';
import '../../css/t/t9h25ryne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_r-5l9bw"/><path class="t9h25ryne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:route-off-filled" /></template>
