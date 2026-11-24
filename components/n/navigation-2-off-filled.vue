<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw-2n_btc.css';
import '../../css/g/gawagji8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw-2n_btc"/><path clip-rule="evenodd" class="gawagji8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:navigation-2-off-filled" /></template>
