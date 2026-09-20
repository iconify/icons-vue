<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdg726bhb.css';
import '../../css/e/e74mzrb2k.css';
import '../../css/v/v_mr9f9tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdg726bhb"/><path clip-rule="evenodd" class="e74mzrb2k"/><path class="v_mr9f9tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:qrcode-2-fill" /></template>
