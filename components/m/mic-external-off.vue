<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxxo95beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mic-external-off" /></template>
<style>
.nxxo95beh {
  fill: currentColor;
  d: path("m9.462 6.766l-3.15-3.15q.234-.103.438-.129t.365-.026q1.039 0 1.77.729q.73.727.73 1.771q0 .2-.031.382t-.123.423m9.385 9.384l-1-1V6.77q0-.98-.664-1.644t-1.643-.665q-.98 0-1.644.665q-.664.664-.664 1.643v3.766l-1-1V6.768q0-1.373.973-2.34q.973-.968 2.334-.968t2.335.968t.973 2.34zm1.308 5.535l-6.923-6.923v2.469q0 1.361-.973 2.334t-2.335.973t-2.334-.973q-.974-.973-.974-2.334h-.769l-.885-8.692h2.035l-4.95-4.962l.708-.708L20.86 20.977zm-8.588-2.811q.665-.664.665-1.643v-3.47l-3.181-3.18l-.666 6.65h-.768q0 .978.664 1.643t1.643.665t1.643-.665");
}

</style>
