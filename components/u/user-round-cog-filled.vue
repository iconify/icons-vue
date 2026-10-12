<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auxij4h6f.css';
import '../../css/b/b_q949lvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="auxij4h6f"/><path class="b_q949lvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-cog-filled" /></template>
