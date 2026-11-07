<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vob1vf30q.css';
import '../../css/l/lcw7lzboe.css';
import '../../css/v/vr5_q7bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vob1vf30q"/><path class="lcw7lzboe"/><path clip-rule="evenodd" class="vr5_q7bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-cross-outline" /></template>
