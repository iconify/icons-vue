<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq6vezb0v.css';
import '../../css/z/z_t71ccqt.css';
import '../../css/l/ltats8egd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq6vezb0v"/><path clip-rule="evenodd" class="z_t71ccqt"/><path class="ltats8egd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scan-eye-filled" /></template>
