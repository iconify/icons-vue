<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzfrftnrw.css';
import '../../css/c/c11vxbbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qzfrftnrw"/><path clip-rule="evenodd" class="c11vxbbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:phonecall-blocked-solid" /></template>
