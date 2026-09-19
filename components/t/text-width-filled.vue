<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5bw_15rv.css';
import '../../css/u/ud4vqp_ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5bw_15rv"/><path class="ud4vqp_ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:text-width-filled" /></template>
