<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0z6e0bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tag-clearance" /></template>
<style>
.s0z6e0bdx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.325 3.825h4.597q1.036.001 1.768.733l8.502 8.503q.733.732.733 1.768q0 1.035-.733 1.767l-4.596 4.596q-.732.733-1.767.733q-1.036 0-1.768-.733l-8.503-8.503q-.732-.731-.733-1.767V6.325q0-2.5 2.5-2.5m9.897 8.486l-6.188.176q-.074.002-.146.019q-.072.016-.14.047q-.067.03-.127.072q-.06.043-.111.097t-.09.116q-.039.063-.066.132q-.026.069-.038.142t-.011.146t.019.146q.016.072.047.14q.03.067.072.127q.043.06.097.111t.116.09t.132.066q.069.026.142.038t.146.011l6.188-.176q.074-.002.146-.019q.072-.016.14-.047q.067-.03.127-.072q.06-.043.111-.097t.09-.116q.039-.063.066-.132q.026-.069.038-.142t.011-.146q-.005-.149-.066-.286t-.169-.238q-.108-.103-.248-.156q-.139-.053-.288-.049");
}

</style>
