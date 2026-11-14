<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofjppkajk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:risk-peril-fire" /></template>
<style>
.ofjppkajk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.174 9.614l-5.788-5.788Q12 1.44 9.614 3.826L3.826 9.614q-2.386 2.386 0 4.772l5.788 5.788q2.386 2.386 4.772 0l5.788-5.788q2.386-2.386 0-4.772M12 17.75q-3.5 0-3.5-3q0-1.038 1.102-2.286q.813-.922.906-1.57q.01-.073.034-.143q.025-.07.063-.133q.037-.064.087-.119t.108-.099t.126-.076q.066-.032.138-.051q.071-.018.145-.022t.147.007q.168.024.31.118q.772.515 1.097 1.313q.166-.224.316-.524q.033-.066.079-.125q.045-.058.101-.107q.055-.048.12-.085q.064-.036.134-.06q.07-.023.143-.032t.147-.004t.145.025t.137.052q.159.079.265.221q1.15 1.533 1.15 3.7q0 3-3.5 3");
}

</style>
