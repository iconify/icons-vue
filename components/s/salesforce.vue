<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypa2l2sjm.css';
import '../../css/l/lymew2x1z.css';
import '../../css/o/o8js7wtch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ypa2l2sjm"/><path class="lymew2x1z"/><path class="o8js7wtch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:salesforce" /></template>
