<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9yg93bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-play" /></template>
<style>
.b9yg93bnc {
  fill: currentColor;
  d: path("M5.77 11.977L2.83 9.039l2.94-2.92l2.919 2.92zM9.807 21v-4.596q-1.467-.125-2.92-.324T4 15.52l.23-1q1.928.478 3.858.681t3.912.203t3.913-.203q1.93-.203 3.856-.682l.231 1q-1.436.362-2.889.56t-2.919.325V21zm.558-14.288q-.674-.673-.674-1.635t.674-1.635T12 2.77t1.635.673q.673.674.673 1.635t-.674 1.635T12 7.385t-1.634-.673m.443 6.576q-.501-.501-.501-1.192q0-.69.5-1.191q.502-.501 1.192-.501t1.191.5q.501.502.501 1.192t-.5 1.192q-.501.5-1.192.5t-1.191-.5m6.183-1.442L15.677 9.54l1.315-2.308h2.574l1.315 2.308l-1.315 2.307z");
}

</style>
