<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssed5rbnb.css';
import '../../css/l/lnyix1bdi.css';
import '../../css/k/kc-nki8ft.css';
import '../../css/s/se42z7b7e.css';
import '../../css/p/pq4odsbzp.css';
import '../../css/j/jlkc5ubla.css';
import '../../css/k/kbxubrbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ssed5rbnb"/><path class="lnyix1bdi"/><path class="kc-nki8ft"/><path class="se42z7b7e"/><path class="pq4odsbzp"/><path class="jlkc5ubla"/><path class="kbxubrbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sketch-wordmark" /></template>
