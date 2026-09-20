<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1iew.css';
import '../../css/v/v-mv1g.css';
import '../../css/y/ydovum.css';
import '../../css/o/omd_kv.css';
import '../../css/c/c27iog.css';
import '../../css/s/so-from-22.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew v-mv1g ydovum"/><path class="iw1iew omd_kv ydovum"/><path class="c27iog iw1iew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:person-remove-filled" /></template>
