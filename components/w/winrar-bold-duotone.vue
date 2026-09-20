<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9i6b7boc.css';
import '../../css/r/rptuzg1jl.css';
import '../../css/a/aazo5tbzy.css';
import '../../css/n/ni915cc4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9i6b7boc"/><path class="rptuzg1jl"/><path class="aazo5tbzy"/><path clip-rule="evenodd" class="ni915cc4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:winrar-bold-duotone" /></template>
