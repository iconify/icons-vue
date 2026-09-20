<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gblqb-qvt.css';
import '../../css/x/xaa7x4xbn.css';
import '../../css/x/x9866xb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gblqb-qvt"/><path clip-rule="evenodd" class="xaa7x4xbn"/><path class="x9866xb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:money-stack-solid" /></template>
