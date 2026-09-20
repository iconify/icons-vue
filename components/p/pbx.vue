<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo6-r_b9m.css';
import '../../css/s/sjw8w__rs.css';
import '../../css/c/c_4mldkyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo6-r_b9m"/><path class="sjw8w__rs"/><path class="c_4mldkyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pbx" /></template>
