<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxn_qk47p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxn_qk47p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:signal-zero" /></template>
