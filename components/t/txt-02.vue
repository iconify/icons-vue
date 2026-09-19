<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw3cgebpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw3cgebpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:txt-02" /></template>
