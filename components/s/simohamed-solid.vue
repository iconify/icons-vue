<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml6fninwt.css';
import '../../css/w/wlyltdbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ml6fninwt"/><path clip-rule="evenodd" class="wlyltdbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:simohamed-solid" /></template>
