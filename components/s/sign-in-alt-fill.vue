<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpanu3zmm.css';
import '../../css/m/mqcc82bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpanu3zmm"/><path class="mqcc82bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:sign-in-alt-fill" /></template>
