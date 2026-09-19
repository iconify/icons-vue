<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k80zmcb_e.css';
import '../../css/a/a4jsaxbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k80zmcb_e"/><path class="a4jsaxbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:picture-solid" /></template>
